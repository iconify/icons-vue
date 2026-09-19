<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfuqshb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tfuqshb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:delivery-truck-filled" /></template>
