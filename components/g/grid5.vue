<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r68q1bzjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r68q1bzjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid5" /></template>
