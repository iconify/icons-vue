<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6krvebbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6krvebbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-v-circle-outline" /></template>
