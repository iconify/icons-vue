<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3-5arf6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="n3-5arf6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hang-gliding" /></template>
