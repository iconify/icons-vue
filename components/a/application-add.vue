<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sph3r42wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sph3r42wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:application-add" /></template>
