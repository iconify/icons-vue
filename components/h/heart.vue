<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0l2ahb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s0l2ahb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:heart" /></template>
