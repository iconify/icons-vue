<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5eyfbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5eyfbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:droplet" /></template>
