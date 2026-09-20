<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukoly_qgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukoly_qgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eye-close-line" /></template>
