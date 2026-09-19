<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnar-68-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnar-68-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bookmark" /></template>
