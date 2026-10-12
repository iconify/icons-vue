<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyf831pac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pyf831pac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:face-slightly-frowning-filled" /></template>
