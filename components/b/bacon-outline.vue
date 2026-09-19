<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-033rbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-033rbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bacon-outline" /></template>
