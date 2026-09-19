<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5lxrlnwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w5lxrlnwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:device-tablet-20-solid" /></template>
