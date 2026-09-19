<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmb74bbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmb74bbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gallbladder-outline-24px" /></template>
