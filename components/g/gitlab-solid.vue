<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfl1y3bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfl1y3bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:gitlab-solid" /></template>
