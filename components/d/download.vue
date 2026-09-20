<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4dzfdcda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4dzfdcda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:download" /></template>
