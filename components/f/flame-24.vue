<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctml66e9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctml66e9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:flame-24" /></template>
