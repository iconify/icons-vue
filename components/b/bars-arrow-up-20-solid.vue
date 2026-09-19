<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_analbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z_analbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-arrow-up-20-solid" /></template>
