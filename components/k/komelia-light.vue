<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1pu22bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1pu22bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komelia-light" /></template>
