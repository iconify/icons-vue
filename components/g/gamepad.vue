<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhcfrs4ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hhcfrs4ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gamepad" /></template>
