<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9dmbc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb9dmbc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:circle-1" /></template>
