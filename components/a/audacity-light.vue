<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjjdp8c7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjjdp8c7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audacity-light" /></template>
