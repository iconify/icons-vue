<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0o66qbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j0o66qbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-4-20-solid" /></template>
