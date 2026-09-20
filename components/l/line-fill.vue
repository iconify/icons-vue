<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz78ohduh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz78ohduh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:line-fill" /></template>
