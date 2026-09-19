<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayapvfw_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ayapvfw_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:edit" /></template>
