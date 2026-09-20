<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fld5_9bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fld5_9bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-fog-solid" /></template>
