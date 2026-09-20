<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n91-pkucr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n91-pkucr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:battery-charging" /></template>
