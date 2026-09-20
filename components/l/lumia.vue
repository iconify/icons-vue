<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho4qyubql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4qyubql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lumia" /></template>
