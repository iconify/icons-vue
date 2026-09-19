<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q174y-b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="q174y-b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:battery-small" /></template>
