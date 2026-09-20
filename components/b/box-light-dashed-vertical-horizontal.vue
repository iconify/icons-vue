<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgj-ambzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bgj-ambzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-dashed-vertical-horizontal" /></template>
