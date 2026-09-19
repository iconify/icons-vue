<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqko1numn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqko1numn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bolt-outline" /></template>
