<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxt8p2blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxt8p2blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-outline" /></template>
