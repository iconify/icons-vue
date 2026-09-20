<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytf1yy1pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytf1yy1pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferretdb" /></template>
