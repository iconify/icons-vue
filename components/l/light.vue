<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl8m4y_2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sl8m4y_2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:light" /></template>
