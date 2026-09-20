<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y09x49bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y09x49bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docker-light" /></template>
