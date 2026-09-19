<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp9j5qfxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp9j5qfxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hand" /></template>
