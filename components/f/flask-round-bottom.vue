<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2dgx96ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="n2dgx96ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:flask-round-bottom" /></template>
