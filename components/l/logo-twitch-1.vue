<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20g7xb6e.css';
import '../../css/o/o557kdpvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h20g7xb6e"/><path class="o557kdpvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-twitch-1" /></template>
