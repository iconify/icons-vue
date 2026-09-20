<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1as4bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd1as4bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bowl-outline" /></template>
