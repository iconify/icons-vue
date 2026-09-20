<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g28rmbcxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g28rmbcxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-joystick-left-16" /></template>
