<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpxqa_bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bpxqa_bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gamepad-20-solid" /></template>
