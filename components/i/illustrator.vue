<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjiqa1bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zjiqa1bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:illustrator" /></template>
