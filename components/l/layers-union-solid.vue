<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj4jy0b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dj4jy0b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-union-solid" /></template>
