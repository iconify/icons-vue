<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsc2t133k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsc2t133k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:android" /></template>
