<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csyj8wbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csyj8wbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:email-outlined" /></template>
