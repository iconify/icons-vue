<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9pcd0eaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9pcd0eaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:inbox-sharp" /></template>
