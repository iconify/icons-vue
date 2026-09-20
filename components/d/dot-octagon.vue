<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5f5335vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="x5f5335vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:dot-octagon" /></template>
