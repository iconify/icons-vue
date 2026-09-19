<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v20lpbcwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":694};
const content = `<path class="v20lpbcwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:grab" /></template>
