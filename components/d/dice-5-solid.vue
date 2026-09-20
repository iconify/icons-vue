<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqlnoibgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqlnoibgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-5-solid" /></template>
