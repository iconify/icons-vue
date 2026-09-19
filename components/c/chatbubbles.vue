<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7_t3jbcz.css';
import '../../css/u/u2b-m9bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7_t3jbcz"/><path class="u2b-m9bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chatbubbles" /></template>
