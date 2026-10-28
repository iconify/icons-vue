<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz5gkxxdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5gkxxdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-from-dot" /></template>
