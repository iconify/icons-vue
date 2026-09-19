<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnz56sb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnz56sb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloud-upload-sharp" /></template>
