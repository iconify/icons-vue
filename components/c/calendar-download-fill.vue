<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc82deb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc82deb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-download-fill" /></template>
