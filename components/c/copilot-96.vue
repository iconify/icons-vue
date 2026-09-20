<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm84y2b2v.css';
import '../../css/e/esmuzmbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":96,"height":96};
const content = `<path class="wm84y2b2v"/><path class="esmuzmbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copilot-96" /></template>
