<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/takuyabsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="takuyabsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-down-right-solid" /></template>
