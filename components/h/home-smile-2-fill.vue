<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr1x9ib_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1x9ib_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-smile-2-fill" /></template>
