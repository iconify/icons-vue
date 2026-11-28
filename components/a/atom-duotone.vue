<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yquh6-eyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yquh6-eyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:atom-duotone" /></template>
