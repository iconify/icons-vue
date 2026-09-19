<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x87cd2g6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x87cd2g6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garbage-plastic" /></template>
