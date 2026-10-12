<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj0bay9ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0bay9ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:columns-2-filled" /></template>
