<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt-v--iiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt-v--iiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flathub" /></template>
