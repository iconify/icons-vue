<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e83e8m8xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e83e8m8xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:leafy-green" /></template>
