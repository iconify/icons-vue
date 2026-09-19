<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btx1b7jeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="btx1b7jeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-dribbble-outline" /></template>
