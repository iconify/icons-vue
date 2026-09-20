<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2tdd54no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="c2tdd54no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:airbnb" /></template>
