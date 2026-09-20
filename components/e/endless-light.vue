<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-qpuzxfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-qpuzxfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:endless-light" /></template>
