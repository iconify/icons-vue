<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj8zh9bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wj8zh9bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-type-filled" /></template>
