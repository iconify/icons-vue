<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4kxfbcij.css';
import '../../css/s/sqhl82lfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y4kxfbcij"/><path class="sqhl82lfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:gift-top-16-solid" /></template>
