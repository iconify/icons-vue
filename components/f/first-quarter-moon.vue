<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwzxxondw.css';
import '../../css/o/o-krqzbpw.css';
import '../../css/k/kfrom7bwt.css';
import '../../css/x/xtbg4jhqc.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/u/usozxnbrm.css';
import '../../css/m/m4_qs971a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hwzxxondw"/><path class="o-krqzbpw"/><path class="kfrom7bwt"/><path class="xtbg4jhqc"/><g class="jn8qy4bru"><circle class="usozxnbrm"/><path class="m4_qs971a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:first-quarter-moon" /></template>
