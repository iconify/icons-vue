<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c66ev-hat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c66ev-hat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:add-column-before-outline" /></template>
