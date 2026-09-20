<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkw8qacnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vkw8qacnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:app" /></template>
