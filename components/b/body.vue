<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o91nh_bfw.css';
import '../../css/j/jn4f7db-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o91nh_bfw"/><path class="jn4f7db-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:body" /></template>
