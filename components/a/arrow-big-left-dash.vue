<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_pc7cb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_pc7cb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-left-dash" /></template>
