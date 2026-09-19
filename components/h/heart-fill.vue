<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxemfjbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxemfjbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:heart-fill" /></template>
