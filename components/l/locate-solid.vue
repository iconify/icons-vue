<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlqjhsouj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlqjhsouj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:locate-solid" /></template>
