<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc5ozhhhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc5ozhhhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-upload" /></template>
