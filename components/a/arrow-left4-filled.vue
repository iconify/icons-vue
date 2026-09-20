<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb911gb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb911gb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left4-filled" /></template>
