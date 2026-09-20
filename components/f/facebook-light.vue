<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpg03oxnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpg03oxnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:facebook-light" /></template>
