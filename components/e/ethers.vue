<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8qh0_bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8qh0_bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ethers" /></template>
