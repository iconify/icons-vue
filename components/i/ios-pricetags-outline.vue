<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9lp8vb8r.css';
import '../../css/g/gezdqco1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9lp8vb8r"/><path class="gezdqco1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pricetags-outline" /></template>
