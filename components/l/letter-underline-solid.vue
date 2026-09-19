<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-zokcuio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-zokcuio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:letter-underline-solid" /></template>
