<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th2o4bz-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th2o4bz-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cline" /></template>
