<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb3bujb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zb3bujb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud-moon-rain" /></template>
