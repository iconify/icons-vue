<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vma_27vqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vma_27vqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-5" /></template>
