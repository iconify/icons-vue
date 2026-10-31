<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hahx5mb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hahx5mb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-ethereum-fill-round" /></template>
