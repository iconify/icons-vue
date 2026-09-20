<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uopdy0hhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uopdy0hhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-6-line" /></template>
