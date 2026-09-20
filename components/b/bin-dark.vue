<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qksq_ubpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qksq_ubpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bin-dark" /></template>
