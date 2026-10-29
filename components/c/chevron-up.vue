<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy2-8fbyk.css';
import '../../css/z/z0vd8mbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy2-8fbyk"/><path class="z0vd8mbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chevron-up" /></template>
