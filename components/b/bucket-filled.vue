<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvt0yqttd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvt0yqttd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bucket-filled" /></template>
