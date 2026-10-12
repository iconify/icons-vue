<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze_k8fjio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_k8fjio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gallery-thumbnails-filled" /></template>
