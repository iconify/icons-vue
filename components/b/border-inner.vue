<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq5xa1f1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq5xa1f1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-inner" /></template>
