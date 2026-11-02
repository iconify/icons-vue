<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of1h860am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of1h860am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-3-line" /></template>
