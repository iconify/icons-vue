<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgl-lsb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kgl-lsb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:history-outline" /></template>
