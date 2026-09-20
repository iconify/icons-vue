<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4x_97bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p4x_97bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hospital-sign-circle-remix" /></template>
