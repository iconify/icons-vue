<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5lrlubhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q5lrlubhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:googleplus" /></template>
