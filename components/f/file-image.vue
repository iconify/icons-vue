<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhix2wr0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="yhix2wr0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-image" /></template>
