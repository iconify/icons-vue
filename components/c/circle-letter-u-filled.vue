<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbn6nc11z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbn6nc11z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-u-filled" /></template>
