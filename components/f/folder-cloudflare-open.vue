<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilzbr0e0d.css';
import '../../css/d/d1ok1f99b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ilzbr0e0d"/><path class="d1ok1f99b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cloudflare-open" /></template>
