<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik3bbzb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ik3bbzb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:axe-filled" /></template>
