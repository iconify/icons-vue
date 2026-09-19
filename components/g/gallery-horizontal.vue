<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1u7v3b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1u7v3b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gallery-horizontal" /></template>
