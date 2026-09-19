<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmkh4p2mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cmkh4p2mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:beamed-note" /></template>
