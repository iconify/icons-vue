<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc32_2shk.css';
import '../../css/c/cfya0ubty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc32_2shk"/><path class="cfya0ubty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrows-switch-duotone" /></template>
