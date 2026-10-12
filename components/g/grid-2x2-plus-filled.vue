<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6pox3bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6pox3bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-2x2-plus-filled" /></template>
