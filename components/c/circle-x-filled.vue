<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwaar8x-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jwaar8x-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-x-filled" /></template>
