<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl_jc-bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl_jc-bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-pointer-fill-round" /></template>
