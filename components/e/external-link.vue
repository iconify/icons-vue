<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1-idtyoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1-idtyoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:external-link" /></template>
