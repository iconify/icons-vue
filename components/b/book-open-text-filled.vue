<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx7l5abtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dx7l5abtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-open-text-filled" /></template>
