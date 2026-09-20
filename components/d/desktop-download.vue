<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy6fc6btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wy6fc6btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:desktop-download" /></template>
