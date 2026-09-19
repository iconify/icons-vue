<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0s3pwbiu.css';
import '../../css/f/f6tq_mbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="a0s3pwbiu"/><path class="f6tq_mbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:cart" /></template>
