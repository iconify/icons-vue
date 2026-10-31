<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px09f3oic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="px09f3oic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-slash-20-solid" /></template>
