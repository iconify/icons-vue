<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l85xkubnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l85xkubnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-circle-left" /></template>
