<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om3pm2bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om3pm2bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-down-left-24" /></template>
