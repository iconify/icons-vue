<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqxx1w4em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqxx1w4em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ghost-solid" /></template>
