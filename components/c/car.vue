<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h17mihbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h17mihbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:car" /></template>
