<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khw0c7fxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khw0c7fxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-activity-fill" /></template>
