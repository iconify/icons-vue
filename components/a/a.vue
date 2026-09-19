<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj69zb_dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fj69zb_dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:a" /></template>
