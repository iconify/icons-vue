<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiw435q6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiw435q6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:download" /></template>
