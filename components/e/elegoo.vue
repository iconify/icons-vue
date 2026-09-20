<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-2sbm6kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-2sbm6kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:elegoo" /></template>
