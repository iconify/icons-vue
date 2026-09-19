<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igjziwzis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="igjziwzis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cc-stripe" /></template>
