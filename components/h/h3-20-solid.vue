<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6i4w3bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a6i4w3bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h3-20-solid" /></template>
