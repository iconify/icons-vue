<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqs2x_bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqs2x_bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-usb-filled" /></template>
