<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb7_btbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb7_btbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-o-mouth" /></template>
