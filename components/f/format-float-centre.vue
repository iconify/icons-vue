<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zptwinr1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zptwinr1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-float-centre" /></template>
