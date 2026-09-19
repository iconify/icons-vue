<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj_r53b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="nj_r53b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:brain" /></template>
