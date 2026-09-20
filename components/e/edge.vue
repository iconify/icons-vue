<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bngtq2bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bngtq2bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:edge" /></template>
