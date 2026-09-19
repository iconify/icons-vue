<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrcok4b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hrcok4b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:car-sport-sharp" /></template>
