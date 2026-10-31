<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2rzysexz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2rzysexz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-w-filled" /></template>
