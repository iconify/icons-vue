<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml0269bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml0269bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-start" /></template>
