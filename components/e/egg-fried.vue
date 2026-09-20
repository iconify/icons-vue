<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yveto87ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yveto87ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:egg-fried" /></template>
