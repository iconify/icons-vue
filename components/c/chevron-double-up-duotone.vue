<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/folet6ddy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="folet6ddy primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-double-up-duotone" /></template>
