<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2npdeblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l2npdeblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hotlinkprotection" /></template>
