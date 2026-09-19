<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqirkfbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xqirkfbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-circle-20-solid" /></template>
