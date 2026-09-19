<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvp6zsbrb.css';
import '../../css/b/bv-ekvb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvp6zsbrb"/><path class="bv-ekvb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-swipe-up" /></template>
