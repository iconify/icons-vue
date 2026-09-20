<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgzhb583y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgzhb583y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-open-remove" /></template>
