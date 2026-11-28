<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0e0veb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v0e0veb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-to-line-duotone" /></template>
