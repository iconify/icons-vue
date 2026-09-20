<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbq8g6v3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbq8g6v3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-diamond-solid" /></template>
