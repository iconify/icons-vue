<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9joz9bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9joz9bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:codecov" /></template>
