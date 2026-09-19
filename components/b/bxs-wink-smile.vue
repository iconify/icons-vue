<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukupz7-sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukupz7-sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-wink-smile" /></template>
