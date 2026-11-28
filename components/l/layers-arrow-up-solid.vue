<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcvifnb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcvifnb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-arrow-up-solid" /></template>
