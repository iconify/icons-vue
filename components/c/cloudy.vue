<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqj6vlb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqj6vlb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloudy" /></template>
