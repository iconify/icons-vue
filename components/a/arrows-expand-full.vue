<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thg9xjb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thg9xjb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrows-expand-full" /></template>
