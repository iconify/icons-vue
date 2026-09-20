<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxb8ywse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxb8ywse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:json" /></template>
