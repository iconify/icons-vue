<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylq9gqi5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ylq9gqi5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-left-20-solid" /></template>
