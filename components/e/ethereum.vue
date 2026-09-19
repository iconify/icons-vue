<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lew2wbclk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lew2wbclk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ethereum" /></template>
