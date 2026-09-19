<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb_kh08lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb_kh08lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:cloud" /></template>
