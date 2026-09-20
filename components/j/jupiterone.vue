<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn5qf3ihp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn5qf3ihp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jupiterone" /></template>
