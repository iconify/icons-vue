<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhr98kbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vhr98kbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:bus" /></template>
