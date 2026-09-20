<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si21m2qws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="si21m2qws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:acquisitions-incorporated" /></template>
