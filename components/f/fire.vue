<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov04gg5zt.css';
import '../../css/j/j1t---_1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ov04gg5zt"/><path class="j1t---_1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:fire" /></template>
