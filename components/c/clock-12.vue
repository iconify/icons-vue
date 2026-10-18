<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7_ncvrna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7_ncvrna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:clock-12" /></template>
