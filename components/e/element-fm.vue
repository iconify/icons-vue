<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9-_4zbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n9-_4zbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:element-fm" /></template>
