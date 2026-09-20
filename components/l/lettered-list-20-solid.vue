<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd2uyy8hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yd2uyy8hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lettered-list-20-solid" /></template>
