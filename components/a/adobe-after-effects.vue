<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl73selcd.css';
import '../../css/z/zusvsjbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl73selcd"/><path class="zusvsjbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-after-effects" /></template>
