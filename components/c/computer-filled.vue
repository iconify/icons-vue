<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu2r_83ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eu2r_83ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:computer-filled" /></template>
