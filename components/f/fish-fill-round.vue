<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6i-_ns_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6i-_ns_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fish-fill-round" /></template>
