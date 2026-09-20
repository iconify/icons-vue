<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb5z5zncd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rb5z5zncd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chartbrew" /></template>
