<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su7aqgb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su7aqgb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-justify" /></template>
