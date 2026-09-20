<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-oaaymkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-oaaymkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down5" /></template>
