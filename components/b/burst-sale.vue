<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3t2mwhtg.css';
import '../../css/c/ckjmv4bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="l3t2mwhtg"/><path class="ckjmv4bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:burst-sale" /></template>
