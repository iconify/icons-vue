<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqcu3rbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqcu3rbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:boxing-bag-hanging-bold" /></template>
