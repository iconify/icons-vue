<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arippd3um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arippd3um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-clock" /></template>
