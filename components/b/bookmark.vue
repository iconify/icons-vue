<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu3c_pbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu3c_pbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:bookmark" /></template>
