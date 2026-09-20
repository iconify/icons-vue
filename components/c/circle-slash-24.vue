<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wst584k2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wst584k2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:circle-slash-24" /></template>
