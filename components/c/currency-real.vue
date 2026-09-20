<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdgb8zclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdgb8zclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-real" /></template>
