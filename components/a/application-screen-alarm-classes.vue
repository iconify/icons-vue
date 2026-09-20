<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp7u0ab4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mp7u0ab4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:application-screen-alarm-classes" /></template>
