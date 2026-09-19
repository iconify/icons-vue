<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc7q_ob4j.css';
import '../../css/o/o7vd0ghvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="oc7q_ob4j"/><path class="o7vd0ghvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flab-b-o" /></template>
