<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5svpcbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5svpcbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:envelope" /></template>
