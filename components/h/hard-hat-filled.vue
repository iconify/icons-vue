<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-y-g2b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-y-g2b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hard-hat-filled" /></template>
