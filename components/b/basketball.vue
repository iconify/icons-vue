<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pazc1b7ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pazc1b7ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:basketball" /></template>
