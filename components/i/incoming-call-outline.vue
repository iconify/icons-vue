<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2_o7ybby.css';
import '../../css/k/k2mmmf-wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2_o7ybby"/><path class="k2mmmf-wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:incoming-call-outline" /></template>
