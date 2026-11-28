<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5f2ztzfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5f2ztzfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:eye-lock" /></template>
