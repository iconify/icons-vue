<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhqdajy5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhqdajy5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-up-from-bracket-outline" /></template>
