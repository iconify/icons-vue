<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z08jcjbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z08jcjbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:add-column" /></template>
