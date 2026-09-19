<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcz4umbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz4umbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevron-last" /></template>
