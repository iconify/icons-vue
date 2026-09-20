<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3biobcti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3biobcti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lightbulb-on" /></template>
