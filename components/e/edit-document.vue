<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l610tobwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l610tobwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:edit-document" /></template>
