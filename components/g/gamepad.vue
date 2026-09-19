<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iutdj93oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="iutdj93oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:gamepad" /></template>
