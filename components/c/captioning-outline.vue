<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb2z7spts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb2z7spts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:captioning-outline" /></template>
