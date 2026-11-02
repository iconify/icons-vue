<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9g1z0buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9g1z0buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-2-line" /></template>
