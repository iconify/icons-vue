<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8a8web1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8a8web1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:framer" /></template>
