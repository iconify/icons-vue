<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuaex634l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xuaex634l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:addalarm" /></template>
