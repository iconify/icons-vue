<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnxhuacyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnxhuacyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock-alert" /></template>
