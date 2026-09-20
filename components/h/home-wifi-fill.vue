<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4s1-v3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4s1-v3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-wifi-fill" /></template>
