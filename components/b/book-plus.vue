<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf-9d60ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-9d60ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:book-plus" /></template>
