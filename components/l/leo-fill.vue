<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5megkblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5megkblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:leo-fill" /></template>
