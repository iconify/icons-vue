<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjsut2bzf.css';
import '../../css/x/x8-n8yhcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jjsut2bzf"/><path class="x8-n8yhcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-social-media-youtube" /></template>
