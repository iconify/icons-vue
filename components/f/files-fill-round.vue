<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy5i8ob_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy5i8ob_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-fill-round" /></template>
