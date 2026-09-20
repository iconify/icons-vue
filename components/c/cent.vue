<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm20vx1_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm20vx1_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:cent" /></template>
