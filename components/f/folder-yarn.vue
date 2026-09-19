<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roar_qb4z.css';
import '../../css/c/cuzr41b_o.css';
import '../../css/d/d6up25bex.css';
import '../../css/z/ziil8acyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="roar_qb4z"/><g class="cuzr41b_o"><path transform="matrix(.09189 0 0 .09115 6.896 6.683)" class="d6up25bex"/><path transform="matrix(.09189 0 0 .09115 6.896 6.683)" class="ziil8acyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-yarn" /></template>
