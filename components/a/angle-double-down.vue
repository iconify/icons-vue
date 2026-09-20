<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf2tv_b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2tv_b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:angle-double-down" /></template>
