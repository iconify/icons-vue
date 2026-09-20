<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hum31150c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hum31150c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-police-light" /></template>
