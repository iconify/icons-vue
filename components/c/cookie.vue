<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmp0c2bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmp0c2bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cookie" /></template>
