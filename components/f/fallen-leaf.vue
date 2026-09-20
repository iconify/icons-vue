<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcdy3zbpl.css';
import '../../css/j/jd002rb2b.css';
import '../../css/p/pdau_gb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kcdy3zbpl"/><path class="jd002rb2b"/><path class="pdau_gb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:fallen-leaf" /></template>
