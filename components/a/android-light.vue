<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3xkf5b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3xkf5b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-light" /></template>
