<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8wh_ubxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8wh_ubxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-right-solid" /></template>
