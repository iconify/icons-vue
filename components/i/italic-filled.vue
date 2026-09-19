<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-z-z9x6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-z-z9x6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:italic-filled" /></template>
