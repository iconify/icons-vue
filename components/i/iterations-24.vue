<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzhiui1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czzhiui1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:iterations-24" /></template>
