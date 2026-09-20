<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuffd7q-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="tuffd7q-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-square-down-right" /></template>
