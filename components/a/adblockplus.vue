<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq8x8nbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq8x8nbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adblockplus" /></template>
