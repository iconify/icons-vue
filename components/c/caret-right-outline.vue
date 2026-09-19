<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fio84ly5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fio84ly5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:caret-right-outline" /></template>
