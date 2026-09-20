<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gksnoabiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gksnoabiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-down-bold" /></template>
