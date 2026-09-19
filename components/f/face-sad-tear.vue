<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8buf-dlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8buf-dlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-sad-tear" /></template>
