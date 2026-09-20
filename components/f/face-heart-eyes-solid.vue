<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdrwnhcxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdrwnhcxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-heart-eyes-solid" /></template>
