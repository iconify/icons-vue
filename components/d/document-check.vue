<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flslc_b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flslc_b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:document-check" /></template>
