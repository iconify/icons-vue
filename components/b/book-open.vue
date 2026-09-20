<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csb89yfwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csb89yfwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:book-open" /></template>
