<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5dmy6b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y5dmy6b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-raised-20-solid" /></template>
