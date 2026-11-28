<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw1kw4huw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw1kw4huw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-medical-plus" /></template>
