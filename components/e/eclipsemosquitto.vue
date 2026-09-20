<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkfl6o0qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkfl6o0qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:eclipsemosquitto" /></template>
