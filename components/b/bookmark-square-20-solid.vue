<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skxv8murs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="skxv8murs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bookmark-square-20-solid" /></template>
