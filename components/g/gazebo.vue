<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr1kvibsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qr1kvibsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gazebo" /></template>
