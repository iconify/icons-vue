<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndsaobw2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndsaobw2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-c" /></template>
