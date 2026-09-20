<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_gzdw1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_gzdw1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-upload-fill" /></template>
