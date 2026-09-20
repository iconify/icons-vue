<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5om8e96x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5om8e96x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-not-equal-variant" /></template>
