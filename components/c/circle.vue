<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo3r6sbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="yo3r6sbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:circle" /></template>
