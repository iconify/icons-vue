<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2sfo7bun.css';
import '../../css/i/i8lgm5omt.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z2sfo7bun"/><path class="i8lgm5omt"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-check-48" /></template>
