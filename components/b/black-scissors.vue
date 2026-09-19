<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od9c0scqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="od9c0scqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-scissors" /></template>
