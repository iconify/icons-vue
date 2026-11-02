<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd4vxhumm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd4vxhumm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:front-fog-lights-fill" /></template>
