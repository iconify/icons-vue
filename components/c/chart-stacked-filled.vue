<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3att8bhb.css';
import '../../css/s/s2tkiab1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3att8bhb"/><path class="s2tkiab1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-stacked-filled" /></template>
