<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eerzfobyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eerzfobyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:briefcase" /></template>
