<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3290zb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x3290zb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-right-20-solid" /></template>
