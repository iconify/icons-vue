<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwl-77ffc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwl-77ffc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-indent-increase" /></template>
