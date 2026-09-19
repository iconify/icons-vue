<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv6xn7b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv6xn7b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:grip-horizontal" /></template>
