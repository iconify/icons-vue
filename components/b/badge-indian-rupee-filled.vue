<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh-c-ubmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh-c-ubmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-indian-rupee-filled" /></template>
