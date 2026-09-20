<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw2xo7ugk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vw2xo7ugk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:alpha" /></template>
