<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvn59fbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvn59fbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-fill" /></template>
