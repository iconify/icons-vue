<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks644wben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="ks644wben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:envelope" /></template>
