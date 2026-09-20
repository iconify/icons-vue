<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgix4xb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bgix4xb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:editor-grid-dots" /></template>
