<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dipnjccbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dipnjccbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:horse-round" /></template>
