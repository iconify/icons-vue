<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-m8hbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-m8hbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bold" /></template>
