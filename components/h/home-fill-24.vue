<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7-q23bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7-q23bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:home-fill-24" /></template>
