<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgx48ktia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgx48ktia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lambda" /></template>
