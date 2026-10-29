<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwc2mnb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwc2mnb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bluetooth-off" /></template>
