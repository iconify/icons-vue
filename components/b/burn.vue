<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g543_ly2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="g543_ly2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:burn" /></template>
