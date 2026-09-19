<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuw2p1vit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuw2p1vit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-07" /></template>
