<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx5jtdgol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="sx5jtdgol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thick-up" /></template>
