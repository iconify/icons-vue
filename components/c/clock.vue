<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tifk5dbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tifk5dbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:clock" /></template>
