<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb8yt5fzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qb8yt5fzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libretranslate-light" /></template>
