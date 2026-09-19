<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu44ccbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu44ccbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:flask-outline" /></template>
