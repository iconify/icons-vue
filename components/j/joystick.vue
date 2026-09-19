<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dix5l05ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dix5l05ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:joystick" /></template>
