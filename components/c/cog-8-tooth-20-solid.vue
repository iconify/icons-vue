<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqrfbbbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mqrfbbbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cog-8-tooth-20-solid" /></template>
