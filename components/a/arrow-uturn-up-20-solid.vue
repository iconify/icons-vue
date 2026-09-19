<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6apakbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l6apakbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-up-20-solid" /></template>
