<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k67fwybvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k67fwybvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookorbit-light" /></template>
