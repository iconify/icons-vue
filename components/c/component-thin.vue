<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihb2-7b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihb2-7b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:component-thin" /></template>
