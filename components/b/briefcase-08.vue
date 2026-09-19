<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljocc-b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljocc-b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-08" /></template>
