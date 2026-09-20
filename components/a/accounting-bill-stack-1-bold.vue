<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a51bl-bho.css';
import '../../css/o/o0un9yhqx.css';
import '../../css/s/snq8qn9hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a51bl-bho"/><path class="o0un9yhqx"/><path class="snq8qn9hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:accounting-bill-stack-1-bold" /></template>
