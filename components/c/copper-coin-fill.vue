<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_1vc6bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_1vc6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copper-coin-fill" /></template>
