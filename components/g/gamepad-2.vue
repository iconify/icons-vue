<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap4pzbctu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap4pzbctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gamepad-2" /></template>
