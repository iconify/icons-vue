<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu9s8wbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu9s8wbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cyberchef-dark" /></template>
