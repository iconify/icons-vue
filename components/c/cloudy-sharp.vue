<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sew8kkscr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sew8kkscr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloudy-sharp" /></template>
