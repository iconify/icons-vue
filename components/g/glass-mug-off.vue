<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6eka7asw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6eka7asw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass-mug-off" /></template>
