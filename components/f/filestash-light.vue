<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5mk3kbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5mk3kbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filestash-light" /></template>
