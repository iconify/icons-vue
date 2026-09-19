<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy4mpxe2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zy4mpxe2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gobackward-10" /></template>
