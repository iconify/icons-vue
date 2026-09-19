<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q51s_lb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q51s_lb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dharmachakra" /></template>
