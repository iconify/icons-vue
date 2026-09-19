<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8x3bri7t.css';
import '../../css/y/yf5edlbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8x3bri7t"/><path class="yf5edlbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:charging-fill" /></template>
