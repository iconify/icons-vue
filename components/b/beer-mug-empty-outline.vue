<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nprwfihuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nprwfihuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:beer-mug-empty-outline" /></template>
