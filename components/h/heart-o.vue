<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmbg9isdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmbg9isdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:heart-o" /></template>
