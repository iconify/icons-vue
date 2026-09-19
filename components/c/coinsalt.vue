<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp6xecb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="vp6xecb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:coinsalt" /></template>
