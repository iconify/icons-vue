<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9yp86lol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g9yp86lol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:direction-alt" /></template>
