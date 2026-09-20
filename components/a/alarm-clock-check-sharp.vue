<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov1f3v2im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov1f3v2im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-check-sharp" /></template>
