<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzjrs5vvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzjrs5vvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:female" /></template>
