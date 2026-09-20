<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzzxu-bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzzxu-bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:branch-line-5" /></template>
