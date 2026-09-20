<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l27puu-7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l27puu-7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:documenso-dark" /></template>
