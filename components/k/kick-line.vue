<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0g4gkbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0g4gkbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:kick-line" /></template>
