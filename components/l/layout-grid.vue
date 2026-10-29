<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-877v1pe.css';
import '../../css/e/e-_uqrb9d.css';
import '../../css/i/ijz6zybvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-877v1pe"/><path class="e-_uqrb9d"/><path class="ijz6zybvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:layout-grid" /></template>
