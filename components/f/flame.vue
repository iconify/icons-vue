<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2upjwmzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":770,"height":1024};
const content = `<path class="d2upjwmzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flame" /></template>
