<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5u1y60je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5u1y60je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:airplane-seat-02" /></template>
