<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n476uizha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n476uizha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fire-hydrant-off" /></template>
