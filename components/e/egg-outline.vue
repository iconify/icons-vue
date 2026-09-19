<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia4i60buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia4i60buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:egg-outline" /></template>
