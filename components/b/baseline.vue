<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_fti0d4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_fti0d4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:baseline" /></template>
