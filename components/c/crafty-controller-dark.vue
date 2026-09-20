<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0f-q8b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0f-q8b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crafty-controller-dark" /></template>
