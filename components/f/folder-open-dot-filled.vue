<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0q4k-bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0q4k-bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-open-dot-filled" /></template>
