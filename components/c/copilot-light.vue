<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk5s5sbxi.css';
import '../../css/e/ecj_qnblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hk5s5sbxi"/><path class="ecj_qnblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:copilot-light" /></template>
