<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryzlypbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ryzlypbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:link-2-duotone" /></template>
