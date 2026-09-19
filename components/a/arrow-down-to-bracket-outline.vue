<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-nilb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-nilb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-down-to-bracket-outline" /></template>
