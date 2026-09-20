<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiu4072ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiu4072ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:link-tiny" /></template>
