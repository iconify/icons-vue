<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg7d5d_ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="tg7d5d_ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:dropbox" /></template>
