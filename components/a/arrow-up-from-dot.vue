<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqzu234pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqzu234pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-from-dot" /></template>
