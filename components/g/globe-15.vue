<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxrp8fbwb.css';
import '../../css/s/sp9j6lqmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yxrp8fbwb"/><path class="sp9j6lqmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:globe-15" /></template>
