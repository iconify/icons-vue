<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9kcw5bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9kcw5bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ab-testing" /></template>
