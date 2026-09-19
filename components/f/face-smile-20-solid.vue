<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytv0zmnmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ytv0zmnmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-smile-20-solid" /></template>
