<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9jziobae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9jziobae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-essential-indoor" /></template>
