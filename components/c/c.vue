<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwq2nyb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwq2nyb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:c" /></template>
