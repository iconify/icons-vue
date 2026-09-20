<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihgfy3ggy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihgfy3ggy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:android" /></template>
