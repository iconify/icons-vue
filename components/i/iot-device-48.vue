<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svwgtwb6l.css';
import '../../css/x/xwg4fnbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="svwgtwb6l"/><path class="xwg4fnbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iot-device-48" /></template>
