<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m96fcwz_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m96fcwz_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-circle-down" /></template>
