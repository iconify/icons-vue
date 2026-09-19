<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daqkvwn8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="daqkvwn8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hourglass-half" /></template>
