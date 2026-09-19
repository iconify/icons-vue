<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aadbtqr2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aadbtqr2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:align-left" /></template>
