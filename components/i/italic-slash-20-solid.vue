<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgyv-v2ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dgyv-v2ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:italic-slash-20-solid" /></template>
