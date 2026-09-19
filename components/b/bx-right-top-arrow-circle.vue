<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyzmj84gk.css';
import '../../css/r/rrzjp2boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyzmj84gk"/><path class="rrzjp2boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-right-top-arrow-circle" /></template>
