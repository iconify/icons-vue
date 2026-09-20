<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h695rk-bi.css';
import '../../css/a/aealofbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h695rk-bi"/><path class="aealofbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-dollar-fill" /></template>
