<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e49b3fbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e49b3fbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:highlight" /></template>
