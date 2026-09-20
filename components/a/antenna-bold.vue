<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta4gnrc5z.css';
import '../../css/n/ncb98mbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta4gnrc5z"/><path class="ncb98mbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:antenna-bold" /></template>
