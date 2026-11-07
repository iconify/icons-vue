<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfg33ubfc.css';
import '../../css/p/pjltp9b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfg33ubfc"/><path class="pjltp9b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-off-bold-duotone" /></template>
