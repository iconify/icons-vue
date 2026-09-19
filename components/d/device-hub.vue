<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk02wmbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="qk02wmbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:device-hub" /></template>
