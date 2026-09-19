<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6g2-ok-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6g2-ok-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:heart" /></template>
