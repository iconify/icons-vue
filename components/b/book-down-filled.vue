<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax_u4j-wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ax_u4j-wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-down-filled" /></template>
