<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cft0r1bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cft0r1bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ansible-light" /></template>
