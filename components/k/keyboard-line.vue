<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne-p80xpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne-p80xpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:keyboard-line" /></template>
