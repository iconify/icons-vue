<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0j-z0w1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0j-z0w1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-left-filled" /></template>
