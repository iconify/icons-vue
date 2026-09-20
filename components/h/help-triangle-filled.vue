<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px1frhb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px1frhb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:help-triangle-filled" /></template>
