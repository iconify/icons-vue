<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1770sb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1770sb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-flat-p" /></template>
