<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyg5cccys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyg5cccys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ign" /></template>
