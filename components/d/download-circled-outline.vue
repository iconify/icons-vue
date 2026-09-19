<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abgf9lb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abgf9lb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:download-circled-outline" /></template>
