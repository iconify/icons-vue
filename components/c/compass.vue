<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkk3whelo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkk3whelo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:compass" /></template>
