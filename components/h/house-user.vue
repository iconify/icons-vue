<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km1ktek-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="km1ktek-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:house-user" /></template>
