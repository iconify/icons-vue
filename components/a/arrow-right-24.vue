<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qymubfnea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qymubfnea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-right-24" /></template>
