<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlrcdvb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlrcdvb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-line" /></template>
