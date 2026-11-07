<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svsjy1b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="svsjy1b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-in-eaved-leanto-shelter" /></template>
