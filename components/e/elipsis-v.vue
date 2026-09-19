<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yha8eqbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yha8eqbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:elipsis-v" /></template>
