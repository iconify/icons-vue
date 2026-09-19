<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzntexeqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzntexeqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:expand" /></template>
