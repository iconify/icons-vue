<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz6p2kbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz6p2kbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brush-filled" /></template>
