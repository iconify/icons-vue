<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-mp1abpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-mp1abpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-leftbar-open-line" /></template>
