<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc70u4buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="vc70u4buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:gift-f" /></template>
