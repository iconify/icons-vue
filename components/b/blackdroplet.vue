<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2kcvmbtw.css';
import '../../css/x/xnsfeobti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2kcvmbtw"/><path class="xnsfeobti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackdroplet" /></template>
