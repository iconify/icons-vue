<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk6nt8u7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk6nt8u7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:longer-ai" /></template>
