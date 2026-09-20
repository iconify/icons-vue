<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eozj1cb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eozj1cb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:arrow-right-up" /></template>
