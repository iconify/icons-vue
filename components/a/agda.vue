<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe7xcbbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe7xcbbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:agda" /></template>
