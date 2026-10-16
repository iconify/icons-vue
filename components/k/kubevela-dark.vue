<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmakjdpxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":122.5,"height":122.5};
const content = `<path class="xmakjdpxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kubevela-dark" /></template>
