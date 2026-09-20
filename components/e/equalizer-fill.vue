<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygd8jqbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygd8jqbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:equalizer-fill" /></template>
