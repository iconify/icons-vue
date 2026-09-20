<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6ldt11qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6ldt11qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-grid-2-fill" /></template>
