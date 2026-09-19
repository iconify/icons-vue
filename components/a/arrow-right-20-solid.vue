<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqkb69uui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="eqkb69uui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right-20-solid" /></template>
