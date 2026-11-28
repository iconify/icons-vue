<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izg17ge-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izg17ge-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:directions-solid" /></template>
