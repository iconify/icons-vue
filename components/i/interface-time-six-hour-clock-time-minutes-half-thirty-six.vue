<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhd5bpl-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yhd5bpl-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-time-six-hour-clock-time-minutes-half-thirty-six" /></template>
