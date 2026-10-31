<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0p3ldb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0p3ldb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-minus-round" /></template>
