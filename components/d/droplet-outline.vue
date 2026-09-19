<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdqopwbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":0.1,"top":0.1};
const content = `<path class="hdqopwbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:droplet-outline" /></template>
