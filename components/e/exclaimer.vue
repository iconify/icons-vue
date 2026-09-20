<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llv0gxble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="llv0gxble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:exclaimer" /></template>
