<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofpbh-bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofpbh-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:barbell-solid" /></template>
