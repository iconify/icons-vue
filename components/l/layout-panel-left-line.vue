<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg6wwbboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6wwbboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-panel-left-line" /></template>
