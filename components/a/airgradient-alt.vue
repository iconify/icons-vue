<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuh6yiurz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuh6yiurz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:airgradient-alt" /></template>
