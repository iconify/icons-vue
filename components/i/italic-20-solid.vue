<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjf65-bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zjf65-bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:italic-20-solid" /></template>
