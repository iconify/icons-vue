<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew902cm0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew902cm0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:laptop-file-outline" /></template>
