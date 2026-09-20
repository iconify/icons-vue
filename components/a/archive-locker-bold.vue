<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2swubccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2swubccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:archive-locker-bold" /></template>
