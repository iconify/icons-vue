<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxc68snwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxc68snwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:directions" /></template>
