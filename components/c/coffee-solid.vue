<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvia1dq0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvia1dq0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:coffee-solid" /></template>
