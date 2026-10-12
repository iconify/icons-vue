<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr8ptachn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr8ptachn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-distribute-center-filled" /></template>
