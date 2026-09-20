<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6almjv6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6almjv6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:components-off" /></template>
