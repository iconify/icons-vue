<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krpr_ibvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krpr_ibvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-lock-open" /></template>
