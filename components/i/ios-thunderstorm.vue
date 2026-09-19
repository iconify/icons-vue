<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g48a6w0ps.css';
import '../../css/x/xwy_3hbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g48a6w0ps"/><path class="xwy_3hbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-thunderstorm" /></template>
