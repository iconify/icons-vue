<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kne2acc8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kne2acc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-shield-x" /></template>
