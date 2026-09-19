<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck3ktbcfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck3ktbcfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calculator" /></template>
