<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wro5ucciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wro5ucciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-down-20-solid" /></template>
