<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rikvh-b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rikvh-b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-rolling-eyes" /></template>
