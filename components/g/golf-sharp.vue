<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioq_pnb1t.css';
import '../../css/x/xde3kv5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ioq_pnb1t"/><path class="xde3kv5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:golf-sharp" /></template>
