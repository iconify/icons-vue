<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqz63jbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqz63jbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-resize" /></template>
