<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2b73tr4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2b73tr4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-a-z" /></template>
