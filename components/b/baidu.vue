<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcznqro8c.css';
import '../../css/g/gsn7st_me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcznqro8c"/><path class="gsn7st_me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:baidu" /></template>
