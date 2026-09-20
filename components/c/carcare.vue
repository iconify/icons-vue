<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_an92bjh.css';
import '../../css/a/aj2v-hbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_an92bjh"/><path class="aj2v-hbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:carcare" /></template>
