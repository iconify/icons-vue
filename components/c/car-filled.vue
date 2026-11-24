<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6fsr3b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h6fsr3b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:car-filled" /></template>
