<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz502wzwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tz502wzwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:kerb-flush" /></template>
