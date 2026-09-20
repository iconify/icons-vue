<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i39u7r_ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i39u7r_ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hdd-16" /></template>
