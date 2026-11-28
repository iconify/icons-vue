<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyjkqb7xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyjkqb7xa primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hash-duotone" /></template>
