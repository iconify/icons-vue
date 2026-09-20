<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r27fyibzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r27fyibzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-down-fill" /></template>
