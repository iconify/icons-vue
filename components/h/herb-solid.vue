<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hua2a4b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hua2a4b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:herb-solid" /></template>
