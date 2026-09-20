<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lztc1r74z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="lztc1r74z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:grab" /></template>
