<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwruimg-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="pwruimg-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:headphones" /></template>
