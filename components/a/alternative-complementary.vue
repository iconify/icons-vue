<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4u4mbc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="q4u4mbc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:alternative-complementary" /></template>
