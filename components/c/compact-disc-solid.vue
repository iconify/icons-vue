<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjhrwr1mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wjhrwr1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:compact-disc-solid" /></template>
