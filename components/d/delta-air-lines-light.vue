<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur2i2bh8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ur2i2bh8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:delta-air-lines-light" /></template>
