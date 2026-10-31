<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfu6rac0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfu6rac0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-medium-fill-round" /></template>
