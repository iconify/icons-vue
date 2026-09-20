<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzvhhsbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzvhhsbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:feed" /></template>
