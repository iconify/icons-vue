<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkft393ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="xkft393ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:explicit" /></template>
