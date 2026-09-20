<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_7ruozfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_7ruozfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-tag" /></template>
