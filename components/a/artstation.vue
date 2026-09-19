<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ppehbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-ppehbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:artstation" /></template>
