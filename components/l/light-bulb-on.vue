<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nio8jccck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nio8jccck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:light-bulb-on" /></template>
