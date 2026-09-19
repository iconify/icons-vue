<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjofz1b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjofz1b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fish-alt-outline" /></template>
