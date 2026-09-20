<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v95o1pkwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v95o1pkwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:globe-off" /></template>
