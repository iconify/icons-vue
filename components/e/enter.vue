<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4hpb_b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4hpb_b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:enter" /></template>
