<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlcn24b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlcn24b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libretranslate-light" /></template>
