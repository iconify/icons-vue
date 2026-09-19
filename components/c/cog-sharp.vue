<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0z58z36m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x0z58z36m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cog-sharp" /></template>
