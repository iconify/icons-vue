<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byfcc--4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byfcc--4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:award-ribbon-star-1-bold" /></template>
