<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-c4arb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-c4arb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flashlight" /></template>
