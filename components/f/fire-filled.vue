<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjer4-bfp.css';
import '../../css/y/yn-kc5b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjer4-bfp"/><path class="yn-kc5b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fire-filled" /></template>
