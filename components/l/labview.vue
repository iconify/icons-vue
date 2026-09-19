<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcbt7yjkc.css';
import '../../css/s/sq6-edbzr.css';
import '../../css/b/bgw48cfvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xcbt7yjkc"/><path class="sq6-edbzr"/><path class="bgw48cfvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:labview" /></template>
