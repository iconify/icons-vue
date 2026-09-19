<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sptmahc8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sptmahc8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:arrow-left" /></template>
