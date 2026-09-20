<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjvg18z4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjvg18z4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:alfred" /></template>
