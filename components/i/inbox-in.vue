<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smet6ccpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smet6ccpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:inbox-in" /></template>
