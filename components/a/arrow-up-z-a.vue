<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wibr-cbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wibr-cbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-z-a" /></template>
