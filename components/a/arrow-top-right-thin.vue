<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5mq17sgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5mq17sgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right-thin" /></template>
