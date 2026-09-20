<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weui-8b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weui-8b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-turn-up-right-expressive" /></template>
