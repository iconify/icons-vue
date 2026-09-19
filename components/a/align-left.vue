<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya2mhfiow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya2mhfiow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-left" /></template>
