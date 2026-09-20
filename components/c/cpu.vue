<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnwf6cc6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnwf6cc6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cpu" /></template>
