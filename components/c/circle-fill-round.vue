<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9i-9-pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co9i-9-pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-fill-round" /></template>
