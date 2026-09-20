<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzjpz52lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzjpz52lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-pause" /></template>
