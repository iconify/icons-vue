<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb5d57cbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pb5d57cbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:email-stroke-20" /></template>
