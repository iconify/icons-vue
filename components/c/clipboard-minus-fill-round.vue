<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kllp8i1cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kllp8i1cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-minus-fill-round" /></template>
