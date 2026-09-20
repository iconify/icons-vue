<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkd4cobqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkd4cobqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:chai" /></template>
