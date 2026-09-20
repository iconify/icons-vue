<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5rwgpn5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g5rwgpn5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-jumping-above-cascade" /></template>
