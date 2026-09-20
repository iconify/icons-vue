<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i78yvwbdu.css';
import '../../css/k/kbwzzybpy.css';
import '../../css/f/fkxqyxbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i78yvwbdu"/><path class="kbwzzybpy"/><path class="fkxqyxbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logwell-dark" /></template>
