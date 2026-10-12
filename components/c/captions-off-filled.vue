<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4xdc-b3f.css';
import '../../css/x/xnw8m44ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4xdc-b3f"/><path class="xnw8m44ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:captions-off-filled" /></template>
