<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmx6jvt0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmx6jvt0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:algolia" /></template>
