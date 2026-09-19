<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcgs8uiau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":374,"height":512};
const content = `<path class="xcgs8uiau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:brotli-old" /></template>
