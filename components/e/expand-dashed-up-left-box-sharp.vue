<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdv4d22pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdv4d22pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-box-sharp" /></template>
