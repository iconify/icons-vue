<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm4hurb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm4hurb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:check-bold" /></template>
