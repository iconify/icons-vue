<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsbwsb98g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gsbwsb98g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:discourse" /></template>
