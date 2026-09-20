<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twadonbqo.css';
import '../../css/u/umps_z5qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="twadonbqo"/><path class="umps_z5qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:joystick-solid" /></template>
