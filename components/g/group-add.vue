<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dact7tbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dact7tbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:group-add" /></template>
