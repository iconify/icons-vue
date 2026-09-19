<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plskvkbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="plskvkbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-arrow-down-20-solid" /></template>
