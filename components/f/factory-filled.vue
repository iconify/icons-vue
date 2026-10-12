<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no1_mybjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no1_mybjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:factory-filled" /></template>
