<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh5x32nps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kh5x32nps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:installatron-light" /></template>
