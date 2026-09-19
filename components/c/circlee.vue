<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xudp2625p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xudp2625p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlee" /></template>
