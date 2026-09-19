<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfexy_bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfexy_bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:envelope-open" /></template>
