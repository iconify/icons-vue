<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn44wv8re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn44wv8re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-download-round" /></template>
