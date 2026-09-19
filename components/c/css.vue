<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asux9-iud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="asux9-iud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:css" /></template>
