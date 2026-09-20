<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khn35wb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="khn35wb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:blood-bag-donation-solid" /></template>
