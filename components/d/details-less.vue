<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/new38nbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="new38nbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:details-less" /></template>
