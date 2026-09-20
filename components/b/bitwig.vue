<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc65xdn8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc65xdn8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bitwig" /></template>
