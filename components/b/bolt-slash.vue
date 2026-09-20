<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2_s99bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2_s99bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bolt-slash" /></template>
