<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp4e-knky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp4e-knky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-fog-filled" /></template>
