<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhrentber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhrentber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:hardware-smart-speaker" /></template>
