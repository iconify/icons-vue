<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/felju3tpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="felju3tpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-auto-adjust" /></template>
