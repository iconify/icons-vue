<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo_0kftwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo_0kftwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authgear-dark" /></template>
