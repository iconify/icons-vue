<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmzsi1y9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmzsi1y9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-checklist-line" /></template>
