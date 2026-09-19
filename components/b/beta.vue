<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro3ba9bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro3ba9bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beta" /></template>
