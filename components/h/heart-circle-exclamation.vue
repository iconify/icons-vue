<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0119uc7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="h0119uc7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:heart-circle-exclamation" /></template>
