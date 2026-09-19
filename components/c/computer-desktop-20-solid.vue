<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp7c5ww4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tp7c5ww4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:computer-desktop-20-solid" /></template>
