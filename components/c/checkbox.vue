<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rybd2si7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rybd2si7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:checkbox" /></template>
