<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h36_77paj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h36_77paj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sun" /></template>
