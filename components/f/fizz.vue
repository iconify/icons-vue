<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdx5jchok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdx5jchok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fizz" /></template>
