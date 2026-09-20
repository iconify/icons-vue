<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxl11ypsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxl11ypsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-horizontal-fill" /></template>
