<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4n8_vkum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4n8_vkum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clovalink-light" /></template>
