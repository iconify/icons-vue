<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muhx-4g7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="muhx-4g7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-question-fill" /></template>
