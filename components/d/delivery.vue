<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hen0ml0nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hen0ml0nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:delivery" /></template>
