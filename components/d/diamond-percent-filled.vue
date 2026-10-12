<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3a9z4yiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3a9z4yiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:diamond-percent-filled" /></template>
