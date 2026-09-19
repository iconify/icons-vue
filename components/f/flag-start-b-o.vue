<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvzfp_pvx.css';
import '../../css/o/oc7q_ob4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zvzfp_pvx"/><path class="oc7q_ob4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flag-start-b-o" /></template>
