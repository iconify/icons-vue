<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzef3x4zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzef3x4zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-bold" /></template>
