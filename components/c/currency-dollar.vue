<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjhz6wbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjhz6wbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-dollar" /></template>
