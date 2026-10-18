<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_21rcbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_21rcbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-0-1" /></template>
