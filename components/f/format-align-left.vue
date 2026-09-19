<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwkmj8bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="bwkmj8bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-align-left" /></template>
