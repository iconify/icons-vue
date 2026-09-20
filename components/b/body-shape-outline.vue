<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnc4whb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnc4whb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-outline" /></template>
