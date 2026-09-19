<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj_8lcczn.css';
import '../../css/x/xy4c9hbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cj_8lcczn"/><path class="xy4c9hbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-poi" /></template>
