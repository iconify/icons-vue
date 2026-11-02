<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acukvtagy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acukvtagy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-pound-2-line" /></template>
