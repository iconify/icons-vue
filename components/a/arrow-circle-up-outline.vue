<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8op9voft.css';
import '../../css/w/wckr9kb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8op9voft"/><path class="wckr9kb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-circle-up-outline" /></template>
