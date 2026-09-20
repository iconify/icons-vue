<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwxqalbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwxqalbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:headphones-solid" /></template>
