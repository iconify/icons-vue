<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx63h-s5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx63h-s5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:beer-opener-bold" /></template>
