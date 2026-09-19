<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0eo731hg.css';
import '../../css/m/mwt8libml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0eo731hg"/><path class="mwt8libml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:alienmonster" /></template>
