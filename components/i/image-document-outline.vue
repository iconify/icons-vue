<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgehhybky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sgehhybky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:image-document-outline" /></template>
