<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw6f8ebgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="aw6f8ebgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:headset-mic" /></template>
