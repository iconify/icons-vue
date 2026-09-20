<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwqd8u50l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xwqd8u50l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:a-frame-signboard" /></template>
