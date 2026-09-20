<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jofhjg7gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jofhjg7gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:less" /></template>
