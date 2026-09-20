<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cickl6b4l.css';
import '../../css/i/i8f6vsb_g.css';
import '../../css/n/n8gcj1byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cickl6b4l"/><path class="i8f6vsb_g"/><path class="n8gcj1byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:instagram-circle" /></template>
