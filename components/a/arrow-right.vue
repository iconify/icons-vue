<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0qgwwbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0qgwwbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-right" /></template>
