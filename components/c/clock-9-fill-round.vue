<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz904xiqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz904xiqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-9-fill-round" /></template>
