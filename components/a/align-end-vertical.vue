<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7r4wbbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7r4wbbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-end-vertical" /></template>
