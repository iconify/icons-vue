<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt68ehb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt68ehb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-round" /></template>
