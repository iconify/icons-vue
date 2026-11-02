<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fchvx2m-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fchvx2m-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-6-fill" /></template>
