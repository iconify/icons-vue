<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewmyn8hoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewmyn8hoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dice-four-solid" /></template>
