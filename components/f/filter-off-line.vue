<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grvlv7q-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grvlv7q-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:filter-off-line" /></template>
