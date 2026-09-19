<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myc39_jik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="myc39_jik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:device-phone-portrait" /></template>
