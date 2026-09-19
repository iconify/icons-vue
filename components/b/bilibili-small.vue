<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psm9o272z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="psm9o272z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bilibili-small" /></template>
