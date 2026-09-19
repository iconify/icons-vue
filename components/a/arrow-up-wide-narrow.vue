<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yac2tbc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yac2tbc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-wide-narrow" /></template>
