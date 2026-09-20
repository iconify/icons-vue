<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlymt9bdv.css';
import '../../css/m/mfwm3ntrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hlymt9bdv"/><path class="mfwm3ntrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crossing-markings-ladder" /></template>
