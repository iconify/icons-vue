<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njaw6lxwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njaw6lxwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-octagram-outline" /></template>
