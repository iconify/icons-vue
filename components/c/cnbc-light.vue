<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fws8j6bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fws8j6bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cnbc-light" /></template>
