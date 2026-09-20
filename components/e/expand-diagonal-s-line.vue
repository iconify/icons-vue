<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn2s-smaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn2s-smaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-diagonal-s-line" /></template>
