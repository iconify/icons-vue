<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvc0acc5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvc0acc5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-waves-solid" /></template>
