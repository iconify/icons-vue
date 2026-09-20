<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6_2om8kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6_2om8kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-neutral-fill" /></template>
