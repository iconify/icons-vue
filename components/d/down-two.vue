<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbgytubxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vbgytubxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:down-two" /></template>
