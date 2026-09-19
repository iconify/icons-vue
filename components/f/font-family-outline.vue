<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du7zlccih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du7zlccih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:font-family-outline" /></template>
