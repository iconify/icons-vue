<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8q6kzbna.css';
import '../../css/a/a25ffhnff.css';
import '../../css/o/o3vxjxbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8q6kzbna"/><path class="a25ffhnff"/><path class="o3vxjxbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-round-48" /></template>
