<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3m30c74w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3m30c74w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:covid-19" /></template>
