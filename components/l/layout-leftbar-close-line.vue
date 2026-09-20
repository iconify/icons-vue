<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acrih_vdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acrih_vdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-leftbar-close-line" /></template>
