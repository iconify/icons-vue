<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrasqh2gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrasqh2gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-e-octagon-solid" /></template>
