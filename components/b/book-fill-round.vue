<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxr7riqlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxr7riqlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-fill-round" /></template>
