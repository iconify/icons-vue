<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obyc-wpuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="obyc-wpuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-alert-alarm-bell-2-alert-bell-ring-notification-alarm" /></template>
