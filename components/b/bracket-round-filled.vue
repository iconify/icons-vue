<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf2sv9bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2sv9bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bracket-round-filled" /></template>
