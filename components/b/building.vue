<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvkp7fb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvkp7fb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:building" /></template>
