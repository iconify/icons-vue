<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_5qd-bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_5qd-bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-star-solid" /></template>
