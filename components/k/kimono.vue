<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar6wt_bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ar6wt_bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kimono" /></template>
