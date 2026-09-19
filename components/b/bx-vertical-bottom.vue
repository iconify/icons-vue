<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiyf_-ueq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiyf_-ueq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-vertical-bottom" /></template>
