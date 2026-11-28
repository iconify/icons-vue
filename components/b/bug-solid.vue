<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_4s1eb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_4s1eb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bug-solid" /></template>
