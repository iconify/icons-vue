<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhp7x1b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhp7x1b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-back-right-off" /></template>
