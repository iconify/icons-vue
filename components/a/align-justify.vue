<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf0x807yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vf0x807yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:align-justify" /></template>
