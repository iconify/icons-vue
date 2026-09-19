<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxwl_cbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxwl_cbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dragonfly" /></template>
