<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-cfmzj2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-cfmzj2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-6-solid" /></template>
