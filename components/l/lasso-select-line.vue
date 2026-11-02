<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idusi2b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idusi2b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lasso-select-line" /></template>
