<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3qfxppay.css';
import '../../css/l/l5yoditpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3qfxppay"/><circle class="l5yoditpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:disc" /></template>
