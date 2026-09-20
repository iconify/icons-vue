<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl0zh5brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0zh5brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-walk" /></template>
