<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi9y0klwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi9y0klwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-data-connection" /></template>
