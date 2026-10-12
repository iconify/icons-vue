<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdraqhbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdraqhbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brain-filled" /></template>
