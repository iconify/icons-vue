<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib8o1bb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib8o1bb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-right-circle-solid" /></template>
