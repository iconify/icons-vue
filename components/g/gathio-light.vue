<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ywkvrys.css';
import '../../css/y/ybd0ybb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9ywkvrys"/><path class="ybd0ybb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gathio-light" /></template>
