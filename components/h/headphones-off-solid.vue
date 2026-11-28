<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y20o_wd6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y20o_wd6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:headphones-off-solid" /></template>
