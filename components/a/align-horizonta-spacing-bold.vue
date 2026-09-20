<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqlxk4byx.css';
import '../../css/g/gxoky2bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqlxk4byx"/><path class="gxoky2bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizonta-spacing-bold" /></template>
