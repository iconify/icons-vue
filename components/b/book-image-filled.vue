<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6tj1xb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6tj1xb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-image-filled" /></template>
