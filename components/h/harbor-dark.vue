<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chjrd3bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="chjrd3bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-dark" /></template>
