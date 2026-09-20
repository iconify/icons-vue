<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-2mylbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-2mylbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-rightbar-open-line" /></template>
