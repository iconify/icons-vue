<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b___szmht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b___szmht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bluetooth-outline" /></template>
