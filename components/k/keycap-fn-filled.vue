<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb1we2zpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rb1we2zpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-fn-filled" /></template>
