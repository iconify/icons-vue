<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eajt0eb1y.css';
import '../../css/i/iz8c3l5-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eajt0eb1y"/><path class="iz8c3l5-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-exclamation-duotone" /></template>
