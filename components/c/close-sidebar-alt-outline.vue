<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbu_oejkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbu_oejkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:close-sidebar-alt-outline" /></template>
