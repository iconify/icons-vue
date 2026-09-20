<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri5cv0bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri5cv0bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dialpad" /></template>
