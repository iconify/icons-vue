<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug3di98ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ug3di98ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:broccoli-filled" /></template>
