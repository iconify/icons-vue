<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgmvd28_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zgmvd28_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:badge-check" /></template>
