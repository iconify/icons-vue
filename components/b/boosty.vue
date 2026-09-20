<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyt75nb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyt75nb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:boosty" /></template>
