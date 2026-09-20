<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6576bc0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6576bc0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:heart-rate" /></template>
