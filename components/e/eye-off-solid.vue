<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wii-i5b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wii-i5b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:eye-off-solid" /></template>
