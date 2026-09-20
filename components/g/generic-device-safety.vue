<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu0jvlbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu0jvlbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-safety" /></template>
