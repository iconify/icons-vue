<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stzldcb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="stzldcb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:exclamation-circle-20-solid" /></template>
