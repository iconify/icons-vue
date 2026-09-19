<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xehppybnx.css';
import '../../css/m/mhx0gfbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xehppybnx"/><path class="mhx0gfbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-sharp-turn-filled" /></template>
