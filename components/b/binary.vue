<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izli1gr-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izli1gr-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:binary" /></template>
