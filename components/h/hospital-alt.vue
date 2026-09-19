<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-h-79ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="w-h-79ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hospital-alt" /></template>
