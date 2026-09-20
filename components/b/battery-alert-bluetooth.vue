<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkhsosb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkhsosb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-alert-bluetooth" /></template>
