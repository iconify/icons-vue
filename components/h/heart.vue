<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpx9cthdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpx9cthdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:heart" /></template>
