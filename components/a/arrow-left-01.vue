<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0n773bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0n773bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-left-01" /></template>
