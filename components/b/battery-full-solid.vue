<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my_j7lbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="my_j7lbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:battery-full-solid" /></template>
