<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip49gjb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ip49gjb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:futbol" /></template>
