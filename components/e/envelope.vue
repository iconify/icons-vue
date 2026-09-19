<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpq5wybqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hpq5wybqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:envelope" /></template>
