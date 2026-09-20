<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixx7vz6ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixx7vz6ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connected" /></template>
