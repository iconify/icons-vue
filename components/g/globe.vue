<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znh_s8bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znh_s8bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:globe" /></template>
