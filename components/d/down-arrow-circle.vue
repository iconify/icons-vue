<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0aqzmb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0aqzmb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:down-arrow-circle" /></template>
