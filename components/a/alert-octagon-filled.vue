<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai99w2ekb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai99w2ekb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alert-octagon-filled" /></template>
