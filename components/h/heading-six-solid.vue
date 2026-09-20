<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tosd-wbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tosd-wbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-six-solid" /></template>
