<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad72fbcvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ad72fbcvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-check-filled" /></template>
