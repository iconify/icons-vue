<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzi1mt9mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzi1mt9mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cliparr-light" /></template>
