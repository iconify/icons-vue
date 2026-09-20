<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2x7se42l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2x7se42l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atria-dark" /></template>
